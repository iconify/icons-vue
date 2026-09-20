<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i50evh99z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i50evh99z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-settings-outline" /></template>
