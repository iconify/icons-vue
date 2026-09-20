<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6x6wlb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o6x6wlb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-top-right" /></template>
