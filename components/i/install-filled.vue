<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp53h7iuv.css';
import '../../css/c/cs02177wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp53h7iuv"/><path class="cs02177wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:install-filled" /></template>
