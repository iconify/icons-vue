<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chif_5b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chif_5b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-favorite-outline" /></template>
