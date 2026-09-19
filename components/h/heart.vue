<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8r0h-bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8r0h-bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart" /></template>
