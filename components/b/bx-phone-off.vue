<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2xo85bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2xo85bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-phone-off" /></template>
