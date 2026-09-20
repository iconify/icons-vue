<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw8u3l8sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw8u3l8sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hydrogen-station" /></template>
