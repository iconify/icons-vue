<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8-j4fbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-j4fbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-lock" /></template>
