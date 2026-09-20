<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1c5o8llx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1c5o8llx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:desktop-computer-1" /></template>
