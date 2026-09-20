<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-p44ubtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-p44ubtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-clock-outline" /></template>
