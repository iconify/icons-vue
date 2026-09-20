<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrlv65jph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lrlv65jph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:attachments-outline" /></template>
