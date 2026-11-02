<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ao6nfns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_ao6nfns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edge-fill" /></template>
