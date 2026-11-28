<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcvup4r4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcvup4r4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-arrow-right" /></template>
