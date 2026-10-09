<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6bq5urfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q6bq5urfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infinity-20" /></template>
