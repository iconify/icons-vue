<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvny9qbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvny9qbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-video-sharp" /></template>
