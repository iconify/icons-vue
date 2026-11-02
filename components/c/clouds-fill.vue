<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd041-bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd041-bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clouds-fill" /></template>
