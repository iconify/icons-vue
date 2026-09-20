<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b26n3db1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b26n3db1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:angry-face" /></template>
