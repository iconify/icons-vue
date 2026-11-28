<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx1sf_bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx1sf_bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:braces-check" /></template>
