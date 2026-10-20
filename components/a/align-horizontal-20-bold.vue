<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi2ll04yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mi2ll04yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-horizontal-20-bold" /></template>
