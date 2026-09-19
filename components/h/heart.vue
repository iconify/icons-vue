<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3xpd3bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3xpd3bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:heart" /></template>
