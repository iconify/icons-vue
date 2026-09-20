<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyaysmb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyaysmb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dog-fill" /></template>
