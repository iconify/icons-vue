<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk4vodsjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk4vodsjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-t-box" /></template>
