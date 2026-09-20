<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyj46dbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj46dbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:light-line" /></template>
