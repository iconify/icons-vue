<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n221nccry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n221nccry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:browser-chrome" /></template>
