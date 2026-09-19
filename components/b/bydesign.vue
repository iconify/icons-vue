<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcat1lb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kcat1lb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bydesign" /></template>
