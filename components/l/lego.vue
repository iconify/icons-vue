<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je28i7o7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je28i7o7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lego" /></template>
