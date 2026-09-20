<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh821mhzp.css';
import '../../css/k/kidrbbcux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zh821mhzp"/><path class="kidrbbcux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:edit" /></template>
