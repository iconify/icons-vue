<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mub4bxbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mub4bxbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-mini-fill" /></template>
