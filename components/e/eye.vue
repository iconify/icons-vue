<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8kz08b1o.css';
import '../../css/x/xl0flj30v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i8kz08b1o"/><path class="xl0flj30v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:eye" /></template>
