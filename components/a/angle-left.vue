<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb7asb_cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zb7asb_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:angle-left" /></template>
