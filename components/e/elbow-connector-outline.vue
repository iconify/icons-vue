<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2ftgfzzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m2ftgfzzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:elbow-connector-outline" /></template>
