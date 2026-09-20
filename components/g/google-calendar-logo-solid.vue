<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg7js8y0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dg7js8y0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-calendar-logo-solid" /></template>
