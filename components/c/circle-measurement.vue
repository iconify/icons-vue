<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk5o7kbjs.css';
import '../../css/v/vem7gutod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jk5o7kbjs"/><path class="vem7gutod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-measurement" /></template>
