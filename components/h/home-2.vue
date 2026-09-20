<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0h42yj7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0h42yj7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:home-2" /></template>
