<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/timrc318u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="timrc318u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christmas-ball-fill" /></template>
