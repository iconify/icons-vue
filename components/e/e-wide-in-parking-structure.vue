<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdsjh737e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tdsjh737e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:e-wide-in-parking-structure" /></template>
