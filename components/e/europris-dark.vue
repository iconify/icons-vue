<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgbsu93mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgbsu93mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:europris-dark" /></template>
