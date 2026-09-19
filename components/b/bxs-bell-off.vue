<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmw53x3_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmw53x3_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bell-off" /></template>
