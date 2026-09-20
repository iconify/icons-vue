<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcm2m96rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcm2m96rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-symbol" /></template>
