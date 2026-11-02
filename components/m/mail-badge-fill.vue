<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvqbbv7zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvqbbv7zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-badge-fill" /></template>
