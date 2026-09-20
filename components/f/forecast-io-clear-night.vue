<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr8hnubib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="vr8hnubib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:forecast-io-clear-night" /></template>
