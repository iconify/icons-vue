<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltuf3vbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltuf3vbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-xaml" /></template>
