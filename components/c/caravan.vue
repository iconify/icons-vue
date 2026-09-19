<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0_3rzbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x0_3rzbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:caravan" /></template>
