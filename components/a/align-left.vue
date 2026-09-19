<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfp_h1hyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfp_h1hyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-left" /></template>
