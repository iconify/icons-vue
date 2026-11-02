<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl17533zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl17533zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chrome-line" /></template>
