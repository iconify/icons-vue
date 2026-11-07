<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbsk9kbsr.css';
import '../../css/i/ionjprbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbsk9kbsr"/><path class="ionjprbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-outline" /></template>
