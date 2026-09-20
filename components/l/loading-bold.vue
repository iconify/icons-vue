<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyn1iab4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyn1iab4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:loading-bold" /></template>
