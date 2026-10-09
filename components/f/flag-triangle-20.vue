<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks0oxbcgz.css';
import '../../css/x/xzejhphye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ks0oxbcgz"/><path class="xzejhphye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-triangle-20" /></template>
