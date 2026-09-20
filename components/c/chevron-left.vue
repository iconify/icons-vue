<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl86v1b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl86v1b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-left" /></template>
