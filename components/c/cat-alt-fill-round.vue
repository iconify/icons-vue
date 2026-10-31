<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yltrsi_xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yltrsi_xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-alt-fill-round" /></template>
