<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxa8g1uva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxa8g1uva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-cancelled" /></template>
