<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/sx312ii4d.css';
import '../../css/h/h5q8bi3ys.css';
import '../../css/z/zbrg6qx3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sx312ii4d"/><path class="h5q8bi3ys"/><path class="zbrg6qx3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-slash" /></template>
