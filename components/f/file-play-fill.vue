<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvbm_uvgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbm_uvgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-play-fill" /></template>
