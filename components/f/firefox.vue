<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiokicbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":764};
const content = `<path class="eiokicbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:firefox" /></template>
