<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueipyhqkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ueipyhqkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:calendar-alt-solid" /></template>
