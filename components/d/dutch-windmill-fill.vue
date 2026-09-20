<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2y77bcrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2y77bcrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dutch-windmill-fill" /></template>
