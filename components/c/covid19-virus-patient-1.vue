<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlej7bzzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlej7bzzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid19-virus-patient-1" /></template>
