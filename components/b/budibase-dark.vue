<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isovy3byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isovy3byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budibase-dark" /></template>
