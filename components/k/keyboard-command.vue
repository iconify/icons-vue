<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nctidhb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nctidhb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:keyboard-command" /></template>
