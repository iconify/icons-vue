<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut1gsgb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut1gsgb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f10" /></template>
