<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rznx5gbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rznx5gbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:chart-bar" /></template>
