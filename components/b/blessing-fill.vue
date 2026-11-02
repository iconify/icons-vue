<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxsjmyb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxsjmyb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:blessing-fill" /></template>
