<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch_l3abug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch_l3abug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-10" /></template>
