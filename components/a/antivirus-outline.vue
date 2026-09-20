<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5gxqgxvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5gxqgxvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:antivirus-outline" /></template>
