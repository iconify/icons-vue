<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n814-dbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n814-dbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chair" /></template>
