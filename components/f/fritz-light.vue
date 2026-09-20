<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf5e126wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf5e126wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fritz-light" /></template>
