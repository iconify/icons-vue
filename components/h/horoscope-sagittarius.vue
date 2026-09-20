<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwv0ewblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwv0ewblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horoscope-sagittarius" /></template>
