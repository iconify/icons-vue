<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugku64bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":512};
const content = `<path class="ugku64bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:influxdata" /></template>
