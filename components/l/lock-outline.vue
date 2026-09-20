<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgh2i2xsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgh2i2xsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:lock-outline" /></template>
