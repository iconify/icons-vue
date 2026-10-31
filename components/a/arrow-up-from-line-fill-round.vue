<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdif4bjbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdif4bjbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-from-line-fill-round" /></template>
