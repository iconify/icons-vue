<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnvcz7_-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnvcz7_-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-full" /></template>
