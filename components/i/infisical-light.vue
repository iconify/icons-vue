<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neu215b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="neu215b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:infisical-light" /></template>
