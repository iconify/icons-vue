<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnm-kh31k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnm-kh31k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-close-corner-fill-round" /></template>
