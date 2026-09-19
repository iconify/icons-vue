<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ctc8bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="q2ctc8bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clipboard" /></template>
