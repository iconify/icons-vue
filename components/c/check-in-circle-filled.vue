<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orvn8w8cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="orvn8w8cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:check-in-circle-filled" /></template>
