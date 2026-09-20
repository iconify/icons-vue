<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1w4zbk0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1w4zbk0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alaska-airlines-dark" /></template>
