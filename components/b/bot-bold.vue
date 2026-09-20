<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pemoh6p9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pemoh6p9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bot-bold" /></template>
