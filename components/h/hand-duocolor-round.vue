<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcd1e9z4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcd1e9z4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-duocolor-round" /></template>
