<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icgmf0-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icgmf0-ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:citrus-2-fill" /></template>
