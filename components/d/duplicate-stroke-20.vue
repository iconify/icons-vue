<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4nvvob8l.css';
import '../../css/d/dcy-hxbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c4nvvob8l"/><path class="dcy-hxbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:duplicate-stroke-20" /></template>
