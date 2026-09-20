<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8goynb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8goynb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-baht-line" /></template>
