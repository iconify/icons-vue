<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxkb7-xri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkb7-xri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevation-rise" /></template>
