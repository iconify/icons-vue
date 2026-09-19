<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io0rh2bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io0rh2bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cut" /></template>
