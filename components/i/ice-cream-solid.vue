<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn8cowbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn8cowbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ice-cream-solid" /></template>
