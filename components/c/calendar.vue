<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6p4noldf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m6p4noldf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:calendar" /></template>
