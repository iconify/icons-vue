<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5y088h5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5y088h5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:concert-rock-1-bold" /></template>
