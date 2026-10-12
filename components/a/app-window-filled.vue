<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u73avcctl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u73avcctl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:app-window-filled" /></template>
