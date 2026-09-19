<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7w8o9bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i7w8o9bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cursor-pointer" /></template>
