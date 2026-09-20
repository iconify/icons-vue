<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v87z8ebkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v87z8ebkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bold" /></template>
