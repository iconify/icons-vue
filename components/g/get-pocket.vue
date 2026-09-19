<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_6x620o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1536};
const content = `<path class="tz_6x620o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:get-pocket" /></template>
