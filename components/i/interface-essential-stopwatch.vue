<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le4ktn-ax.css';
import '../../css/q/qfz352b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="le4ktn-ax"/><path class="qfz352b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-stopwatch" /></template>
