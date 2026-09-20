<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1evfbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xm1evfbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-horizontal-outline" /></template>
