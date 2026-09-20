<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb-js9b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sb-js9b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eraser-circle-bold" /></template>
