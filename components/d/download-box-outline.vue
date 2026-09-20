<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwmqbfb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwmqbfb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-box-outline" /></template>
