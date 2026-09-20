<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwg4w1bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iwg4w1bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:input-box-solid" /></template>
