<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm2s2x7kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm2s2x7kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-round" /></template>
