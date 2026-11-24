<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nho7-9bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nho7-9bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flag-triangle-left-filled" /></template>
