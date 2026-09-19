<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh2uq7v6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh2uq7v6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:adjustments-horizontal" /></template>
