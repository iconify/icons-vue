<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epu8qq1sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epu8qq1sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:claude" /></template>
