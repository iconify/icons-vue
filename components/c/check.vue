<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vomlb2-jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vomlb2-jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:check" /></template>
