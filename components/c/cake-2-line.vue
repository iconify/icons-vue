<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0dwpu11b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0dwpu11b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cake-2-line" /></template>
