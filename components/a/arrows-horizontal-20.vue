<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0pjpe9ss.css';
import '../../css/o/ols5a6b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w0pjpe9ss"/><path class="ols5a6b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-horizontal-20" /></template>
