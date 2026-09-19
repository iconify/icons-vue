<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfaz84aqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfaz84aqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-expand" /></template>
