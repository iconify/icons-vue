<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auu_2cchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="auu_2cchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:globe" /></template>
