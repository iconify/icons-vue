<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if9kuxbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if9kuxbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cursor-click" /></template>
