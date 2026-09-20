<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm3y6d_0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dm3y6d_0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ltr" /></template>
