<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nna1dobij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nna1dobij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-prime-video-dark" /></template>
