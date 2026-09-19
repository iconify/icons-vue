<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkskkgb5x.css';
import '../../css/n/nek1lu3pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkskkgb5x"/><path class="nek1lu3pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-dropleft" /></template>
