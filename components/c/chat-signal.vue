<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyx524bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nyx524bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chat-signal" /></template>
