<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4sditc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q4sditc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garlic-hub-dark" /></template>
