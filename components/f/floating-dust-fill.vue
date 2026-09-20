<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7lzrvnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vn7lzrvnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:floating-dust-fill" /></template>
