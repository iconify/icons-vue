<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r417itu3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r417itu3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-100" /></template>
