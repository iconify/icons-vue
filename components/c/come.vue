<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0l9478oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0l9478oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:come" /></template>
