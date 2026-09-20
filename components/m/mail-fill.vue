<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs58peb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs58peb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-fill" /></template>
