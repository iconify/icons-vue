<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufx6883fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufx6883fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-2-fill" /></template>
