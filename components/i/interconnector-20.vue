<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nboi0qbgb.css';
import '../../css/z/zhh6u5bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nboi0qbgb"/><path class="zhh6u5bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:interconnector-20" /></template>
