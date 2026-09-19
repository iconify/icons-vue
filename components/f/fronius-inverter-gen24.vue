<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rteos1-3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rteos1-3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fronius-inverter-gen24" /></template>
