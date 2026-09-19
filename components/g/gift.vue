<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzyfxg1lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rzyfxg1lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:gift" /></template>
