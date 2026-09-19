<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0_0w2ecl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0_0w2ecl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:garmin" /></template>
