<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en4jbhc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en4jbhc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dim-sum-01" /></template>
