<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5iniq7nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r5iniq7nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:classical-building-with-flag" /></template>
