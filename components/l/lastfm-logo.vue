<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh1sgnwon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh1sgnwon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lastfm-logo" /></template>
