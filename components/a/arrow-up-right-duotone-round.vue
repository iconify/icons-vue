<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkxip9b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkxip9b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-duotone-round" /></template>
