<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oefg2-ghd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oefg2-ghd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:calendar" /></template>
