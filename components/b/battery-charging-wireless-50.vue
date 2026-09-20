<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnd1_cdki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnd1_cdki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-50" /></template>
