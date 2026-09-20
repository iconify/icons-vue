<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwy41vlmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwy41vlmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:framer-logo-block" /></template>
