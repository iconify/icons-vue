<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reurb0bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="reurb0bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:face-grinning-solid-expressive" /></template>
