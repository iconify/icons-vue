<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do_g2d87h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="do_g2d87h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lbc" /></template>
