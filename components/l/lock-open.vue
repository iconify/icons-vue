<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-2gwjbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-2gwjbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:lock-open" /></template>
