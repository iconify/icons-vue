<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktndi-n6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktndi-n6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:iphone-old-apps-line" /></template>
