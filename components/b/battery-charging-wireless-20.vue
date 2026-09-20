<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m392x3rmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m392x3rmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-20" /></template>
