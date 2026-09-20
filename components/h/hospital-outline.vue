<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc3gwchtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sc3gwchtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hospital-outline" /></template>
