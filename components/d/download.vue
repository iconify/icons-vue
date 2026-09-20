<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnfat0bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnfat0bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:download" /></template>
