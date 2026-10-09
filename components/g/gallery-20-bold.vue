<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7aql7bvn.css';
import '../../css/j/j652cjm3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7aql7bvn"/><path class="j652cjm3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gallery-20-bold" /></template>
