<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma2jnib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ma2jnib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:function" /></template>
