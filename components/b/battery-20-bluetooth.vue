<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfeyp42jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfeyp42jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-20-bluetooth" /></template>
