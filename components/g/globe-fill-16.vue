<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjjawjfov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sjjawjfov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:globe-fill-16" /></template>
