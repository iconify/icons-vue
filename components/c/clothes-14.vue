<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbh0f59lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lbh0f59lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:clothes-14" /></template>
