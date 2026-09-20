<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ird4xpdhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ird4xpdhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hulu" /></template>
