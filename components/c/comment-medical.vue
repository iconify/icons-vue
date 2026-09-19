<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvzy6fb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvzy6fb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment-medical" /></template>
