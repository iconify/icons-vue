<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkztq_bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rkztq_bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fork-knife" /></template>
