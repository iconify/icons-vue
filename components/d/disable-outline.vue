<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0vwqibqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q0vwqibqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:disable-outline" /></template>
