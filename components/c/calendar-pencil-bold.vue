<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6dt8aclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p6dt8aclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-pencil-bold" /></template>
