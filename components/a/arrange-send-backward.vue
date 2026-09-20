<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wslbe0b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wslbe0b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrange-send-backward" /></template>
