<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5whyy_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl5whyy_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aurral-dark" /></template>
