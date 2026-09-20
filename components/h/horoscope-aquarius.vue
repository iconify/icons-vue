<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsdajwb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsdajwb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horoscope-aquarius" /></template>
