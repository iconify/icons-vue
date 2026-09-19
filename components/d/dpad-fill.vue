<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ugyti7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7ugyti7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dpad-fill" /></template>
