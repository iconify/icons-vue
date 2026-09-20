<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lafypubwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lafypubwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:head-side-mask" /></template>
