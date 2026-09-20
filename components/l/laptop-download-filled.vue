<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc_vo_1qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc_vo_1qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop-download-filled" /></template>
