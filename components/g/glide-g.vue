<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew63x3ajk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ew63x3ajk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:glide-g" /></template>
