<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zihp_4bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zihp_4bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:diamond" /></template>
