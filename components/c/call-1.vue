<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meoj66rlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="meoj66rlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:call-1" /></template>
