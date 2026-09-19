<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb26qubmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nb26qubmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-xmark" /></template>
