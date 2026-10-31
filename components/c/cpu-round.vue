<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svui8mbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svui8mbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-round" /></template>
