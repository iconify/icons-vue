<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuz_j3b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuz_j3b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-find-outline" /></template>
