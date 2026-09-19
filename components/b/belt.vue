<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/npljkgdue.css';
import '../../css/j/j5htyubja.css';
import '../../css/o/oem2-9olf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npljkgdue"/><path class="j5htyubja"/><path class="oem2-9olf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:belt" /></template>
