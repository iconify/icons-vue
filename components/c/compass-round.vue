<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnr41pbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnr41pbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:compass-round" /></template>
