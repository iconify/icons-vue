<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj3z4_bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj3z4_bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-off" /></template>
