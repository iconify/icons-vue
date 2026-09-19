<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orpglcbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":508,"height":512};
const content = `<path class="orpglcbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:csound" /></template>
