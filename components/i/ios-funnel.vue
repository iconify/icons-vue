<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4_09-bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4_09-bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-funnel" /></template>
