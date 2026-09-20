<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo8g0tjqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo8g0tjqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:award-line" /></template>
