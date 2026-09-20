<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx-ngb3xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cx-ngb3xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coughing-face-with-phlegm-in-circle" /></template>
