<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3tuvepm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di3tuvepm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-right" /></template>
