<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbocnv20s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbocnv20s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:col-resize" /></template>
