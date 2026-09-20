<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_gb4cchh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_gb4cchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-rotate-filled" /></template>
