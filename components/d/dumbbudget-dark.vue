<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6f5scbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6f5scbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbbudget-dark" /></template>
