<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f89pw3byy.css';
import '../../css/d/d2jw_nbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f89pw3byy"/><path class="d2jw_nbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-microphone-alt" /></template>
