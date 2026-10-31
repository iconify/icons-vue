<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmj2bc85f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmj2bc85f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-minus-corner-fill-round" /></template>
