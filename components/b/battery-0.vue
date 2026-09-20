<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f72dkd3ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f72dkd3ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-0" /></template>
