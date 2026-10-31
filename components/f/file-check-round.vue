<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxe8bc6ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxe8bc6ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-check-round" /></template>
