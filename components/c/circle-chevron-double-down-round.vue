<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfb3wtbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfb3wtbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-down-round" /></template>
