<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8hocc1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vq8hocc1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:chat" /></template>
