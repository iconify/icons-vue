<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-jp7lbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-jp7lbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-fill" /></template>
