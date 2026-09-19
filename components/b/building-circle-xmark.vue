<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zryp4sb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zryp4sb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-circle-xmark" /></template>
