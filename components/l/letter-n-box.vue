<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz2t82xpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2t82xpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-n-box" /></template>
