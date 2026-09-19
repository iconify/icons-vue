<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf6rktajg.css';
import '../../css/f/fd0ve6bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf6rktajg"/><path class="fd0ve6bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:calendar" /></template>
