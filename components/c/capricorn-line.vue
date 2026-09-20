<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0mdmyy9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0mdmyy9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capricorn-line" /></template>
