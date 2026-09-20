<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8eq42bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8eq42bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brightness-6" /></template>
