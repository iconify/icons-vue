<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-jafa0z.css';
import '../../css/l/lgw0k4bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-jafa0z"/><path class="lgw0k4bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-download-filled" /></template>
