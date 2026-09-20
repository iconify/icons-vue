<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip8n-4bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8n-4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:briefcase" /></template>
