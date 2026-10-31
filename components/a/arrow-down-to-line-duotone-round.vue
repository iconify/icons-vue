<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll1oe2bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll1oe2bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-to-line-duotone-round" /></template>
