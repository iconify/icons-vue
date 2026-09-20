<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl4nh39pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl4nh39pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crosshairs-off" /></template>
