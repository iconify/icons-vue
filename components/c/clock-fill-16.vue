<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ne6lb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t3ne6lb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:clock-fill-16" /></template>
