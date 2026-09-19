<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sknu5wjce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sknu5wjce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diamond-01" /></template>
