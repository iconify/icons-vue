<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywc1ct_vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywc1ct_vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-folder-robot-solid" /></template>
