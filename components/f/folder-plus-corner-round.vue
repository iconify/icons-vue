<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/musbj6buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="musbj6buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-plus-corner-round" /></template>
