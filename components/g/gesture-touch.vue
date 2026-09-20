<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqxpa1b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqxpa1b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-touch" /></template>
