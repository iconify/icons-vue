<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7_iv4ssr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7_iv4ssr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:color-wheel-filled" /></template>
