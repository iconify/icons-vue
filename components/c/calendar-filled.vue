<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7_go48_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v7_go48_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:calendar-filled" /></template>
