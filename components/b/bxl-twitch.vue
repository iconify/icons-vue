<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el4xv0b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el4xv0b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-twitch" /></template>
