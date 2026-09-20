<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnd1kubmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnd1kubmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:credit-card-2-solid" /></template>
