<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulc_957tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulc_957tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:counter-clockwise-clock" /></template>
