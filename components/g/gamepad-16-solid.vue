<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyscnr3nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qyscnr3nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gamepad-16-solid" /></template>
