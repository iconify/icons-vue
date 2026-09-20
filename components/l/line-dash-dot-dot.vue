<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hea10li5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hea10li5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:line-dash-dot-dot" /></template>
