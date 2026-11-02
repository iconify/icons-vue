<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl7lqyb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl7lqyb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-4-line" /></template>
