<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5z8zbx-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v5z8zbx-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-pencil-light" /></template>
