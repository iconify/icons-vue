<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqvl_23_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqvl_23_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eclipse-mosquitto" /></template>
