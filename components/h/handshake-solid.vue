<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmnso2bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fmnso2bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:handshake-solid" /></template>
