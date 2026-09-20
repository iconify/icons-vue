<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-3qw_iec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="n-3qw_iec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-right-stipple-up-right" /></template>
