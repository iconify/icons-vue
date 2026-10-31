<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/hne11ibsr.css';
import '../../css/l/lb8hj9bbj.css';
import '../../css/m/mz8gxwbqy.css';
import '../../css/v/vku-jgsjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="hne11ibsr wm-shadow"/><path class="lb8hj9bbj wm-shadow"/><path class="mz8gxwbqy"/><path class="vku-jgsjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:axe" /></template>
