<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdrxi_5qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mdrxi_5qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:caret-vertical-circle-outline" /></template>
