<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkxo5wbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkxo5wbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-wine" /></template>
