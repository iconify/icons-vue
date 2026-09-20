<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpgil6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpgil6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-60" /></template>
