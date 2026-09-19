<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul6d8o8hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ul6d8o8hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bytedance" /></template>
