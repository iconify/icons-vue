<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy525o-xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy525o-xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-10-round" /></template>
