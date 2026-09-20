<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj6qfrb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bj6qfrb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-yen-yuan" /></template>
