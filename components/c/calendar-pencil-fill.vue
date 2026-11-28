<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayv_5ub6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ayv_5ub6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-pencil-fill" /></template>
