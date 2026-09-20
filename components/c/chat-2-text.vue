<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc5uqub2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc5uqub2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chat-2-text" /></template>
