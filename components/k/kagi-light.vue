<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxk0zwqnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxk0zwqnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kagi-light" /></template>
