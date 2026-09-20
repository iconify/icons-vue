<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e-_vfpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6e-_vfpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-x" /></template>
