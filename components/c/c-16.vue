<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avrw6g-oj.css';
import '../../css/u/udo50kb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="avrw6g-oj"/><path class="udo50kb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:c-16" /></template>
