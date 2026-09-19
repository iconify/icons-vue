<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trhm6wb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trhm6wb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dialpad-filled" /></template>
