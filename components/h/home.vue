<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32an4f6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h32an4f6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:home" /></template>
