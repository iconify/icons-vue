<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhhznw4hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhhznw4hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-lock" /></template>
