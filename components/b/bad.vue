<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zko268h_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zko268h_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bad" /></template>
