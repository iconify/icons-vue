<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol0wd5rgv.css';
import '../../css/w/wkt-wub-t.css';
import '../../css/e/e4zi4ibxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ol0wd5rgv"/><path class="wkt-wub-t"/><path class="e4zi4ibxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ferris-wheel-20-bold" /></template>
