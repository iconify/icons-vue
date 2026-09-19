<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4gmmqchl.css';
import '../../css/r/rhqsj1c8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="k4gmmqchl"/><path class="rhqsj1c8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail-outline" /></template>
