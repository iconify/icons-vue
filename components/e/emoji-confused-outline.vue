<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihuxelobz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihuxelobz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-confused-outline" /></template>
