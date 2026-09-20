<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q55-hx4eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q55-hx4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horoscope-libra" /></template>
