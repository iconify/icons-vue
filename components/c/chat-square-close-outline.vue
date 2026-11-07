<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf9vpac5p.css';
import '../../css/u/um_zvyb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf9vpac5p"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-close-outline" /></template>
