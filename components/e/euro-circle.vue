<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq34stb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vq34stb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:euro-circle" /></template>
