<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g55zcebja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g55zcebja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horoscope-scorpio" /></template>
