<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/nbb1ftj4o.css';
import '../../css/o/o9oyw409s.css';
import '../../css/t/tjnqk450w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nbb1ftj4o"/><path class="o9oyw409s"/><path class="tjnqk450w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layers-02" /></template>
