<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z72316buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z72316buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-seven-outline" /></template>
