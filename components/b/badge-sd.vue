<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj2r2fivx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rj2r2fivx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:badge-sd" /></template>
