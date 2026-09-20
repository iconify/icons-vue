<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8qgik12h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p8qgik12h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-bold" /></template>
