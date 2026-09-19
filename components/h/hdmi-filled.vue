<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oirm5y_yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oirm5y_yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hdmi-filled" /></template>
