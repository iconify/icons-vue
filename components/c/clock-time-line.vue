<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdv6n5bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdv6n5bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-time-line" /></template>
