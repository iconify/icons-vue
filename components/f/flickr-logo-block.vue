<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsl6rs1ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fsl6rs1ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flickr-logo-block" /></template>
