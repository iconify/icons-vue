<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssbwvbbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssbwvbbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-left" /></template>
