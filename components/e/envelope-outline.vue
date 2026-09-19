<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjkr4gbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjkr4gbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:envelope-outline" /></template>
