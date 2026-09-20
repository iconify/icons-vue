<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb0t-15qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb0t-15qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dot" /></template>
