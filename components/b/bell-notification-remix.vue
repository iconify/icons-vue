<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys-ja_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ys-ja_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bell-notification-remix" /></template>
