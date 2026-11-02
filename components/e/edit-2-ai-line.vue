<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvvo5_beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvvo5_beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-2-ai-line" /></template>
