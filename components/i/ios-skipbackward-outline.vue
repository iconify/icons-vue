<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqkalragn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gqkalragn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-skipbackward-outline" /></template>
