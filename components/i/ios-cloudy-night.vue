<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s04t-wbch.css';
import '../../css/o/ordjzlbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s04t-wbch"/><path class="ordjzlbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloudy-night" /></template>
