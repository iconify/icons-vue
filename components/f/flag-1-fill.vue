<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaifu8bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaifu8bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-1-fill" /></template>
