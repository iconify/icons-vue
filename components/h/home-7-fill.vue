<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfaayzmqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfaayzmqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-7-fill" /></template>
