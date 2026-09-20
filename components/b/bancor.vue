<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zev6fxbep.css';
import '../../css/p/pj_m2ybgk.css';
import '../../css/v/v0uywbt6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":269.57,"height":90.72};
const content = `<path class="zev6fxbep"/><path class="pj_m2ybgk"/><path class="v0uywbt6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bancor" /></template>
