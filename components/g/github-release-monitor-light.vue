<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-g771bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-g771bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-release-monitor-light" /></template>
