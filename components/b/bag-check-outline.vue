<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zydcpabso.css';
import '../../css/x/xdj82wxwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zydcpabso"/><path class="xdj82wxwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-check-outline" /></template>
