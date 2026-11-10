<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgdwhabwq.css';
import '../../css/w/wozco6-eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdwhabwq"/><path clip-rule="evenodd" class="wozco6-eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-ban-filled" /></template>
