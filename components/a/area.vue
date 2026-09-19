<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmti31bmb.css';
import '../../css/g/g-1rbpbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmti31bmb"/><path class="g-1rbpbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:area" /></template>
