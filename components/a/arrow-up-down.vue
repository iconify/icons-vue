<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dso2jklbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dso2jklbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-down" /></template>
