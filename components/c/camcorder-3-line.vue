<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lasmuzh_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lasmuzh_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-3-line" /></template>
