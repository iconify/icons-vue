<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrqeybr-c.css';
import '../../css/o/o1embaboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qrqeybr-c"/><path class="o1embaboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:color-palette" /></template>
