<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mrli8m4nv.css';
import '../../css/b/bly0oihkk.css';
import '../../css/v/v88mtsb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="mrli8m4nv"/><path class="bly0oihkk"/><path class="v88mtsb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lasso" /></template>
