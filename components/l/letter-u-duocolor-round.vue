<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nggfwi-6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nggfwi-6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-u-duocolor-round" /></template>
