<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzwd7eu8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzwd7eu8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-down-circle" /></template>
