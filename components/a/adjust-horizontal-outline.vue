<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guldctbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="guldctbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-horizontal-outline" /></template>
