<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbup9w5tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbup9w5tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-bulleted-triangle" /></template>
