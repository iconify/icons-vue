<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbpzq3urk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbpzq3urk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-fill" /></template>
