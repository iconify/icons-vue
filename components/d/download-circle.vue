<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiclth24j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiclth24j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-circle" /></template>
