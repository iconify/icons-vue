<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mec9bobet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mec9bobet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-heart-fill" /></template>
