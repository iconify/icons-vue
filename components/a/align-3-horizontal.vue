<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g9wg6oj_y.css';
import '../../css/c/ceigb7b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(-90 12 17.333)" class="g9wg6oj_y"/><rect transform="rotate(-90 12 6.667)" class="ceigb7b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-3-horizontal" /></template>
