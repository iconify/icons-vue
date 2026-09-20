<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbu1lpb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbu1lpb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-right" /></template>
