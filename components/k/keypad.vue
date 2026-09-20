<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzg4uy75u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzg4uy75u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keypad" /></template>
