<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyde3bcxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyde3bcxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jpeg-logo" /></template>
