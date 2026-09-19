<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbmekrbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbmekrbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:aquarium" /></template>
