<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lla5rtc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lla5rtc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lasso" /></template>
