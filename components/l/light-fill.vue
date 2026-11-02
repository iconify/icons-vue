<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slf_ohb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slf_ohb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:light-fill" /></template>
