<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltx-teboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ltx-teboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-lab-fill" /></template>
