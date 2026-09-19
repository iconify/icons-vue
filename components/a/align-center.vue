<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sul6zry_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sul6zry_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:align-center" /></template>
