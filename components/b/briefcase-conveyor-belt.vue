<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le9v28bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le9v28bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-conveyor-belt" /></template>
