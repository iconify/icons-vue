<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i50ucibha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i50ucibha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-moon-solid" /></template>
