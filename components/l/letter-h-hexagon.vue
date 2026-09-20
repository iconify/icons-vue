<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkpsd5cgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpsd5cgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-hexagon" /></template>
