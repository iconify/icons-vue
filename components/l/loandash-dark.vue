<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec9ynkbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec9ynkbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loandash-dark" /></template>
