<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh7b0fb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh7b0fb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-o-bulk-round" /></template>
