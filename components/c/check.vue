<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxosiwbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="rxosiwbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:check" /></template>
