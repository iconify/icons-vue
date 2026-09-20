<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/nw21fqb1s.css';
import '../../css/r/r9hyg7b7k.css';
import '../../css/p/p9-zrkb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nw21fqb1s"/><path class="r9hyg7b7k"/><path class="p9-zrkb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bucket-circle2" /></template>
