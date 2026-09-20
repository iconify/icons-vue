<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscdasb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vscdasb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:info-square-bold" /></template>
