<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_d0fh6vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_d0fh6vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:immunization-off" /></template>
