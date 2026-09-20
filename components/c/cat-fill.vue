<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tde0x7ylw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tde0x7ylw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cat-fill" /></template>
