<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpbrlabrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cpbrlabrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:bar-chart" /></template>
