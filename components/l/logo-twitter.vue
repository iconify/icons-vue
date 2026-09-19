<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_m5myd5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_m5myd5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-twitter" /></template>
