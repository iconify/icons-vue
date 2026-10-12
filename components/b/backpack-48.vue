<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh6gu7bbw.css';
import '../../css/u/utcfm6g2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nh6gu7bbw"/><path class="utcfm6g2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:backpack-48" /></template>
