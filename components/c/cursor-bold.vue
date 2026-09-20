<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svndefbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svndefbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-bold" /></template>
