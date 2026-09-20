<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwda_fpmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwda_fpmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dumbbell-1" /></template>
