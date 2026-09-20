<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxv7-tb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rxv7-tb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:linkedin-original" /></template>
