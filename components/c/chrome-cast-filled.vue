<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw5x7qc2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dw5x7qc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chrome-cast-filled" /></template>
