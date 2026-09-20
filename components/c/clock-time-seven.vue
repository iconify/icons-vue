<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nabu3x5no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nabu3x5no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-seven" /></template>
