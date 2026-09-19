<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sydt2ty0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":496};
const content = `<path class="sydt2ty0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:globe" /></template>
