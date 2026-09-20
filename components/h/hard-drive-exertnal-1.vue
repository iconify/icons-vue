<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc9v-pb0v.css';
import '../../css/i/i79qx-ncx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc9v-pb0v"/><path class="i79qx-ncx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:hard-drive-exertnal-1" /></template>
