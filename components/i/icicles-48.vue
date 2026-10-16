<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgupoibyg.css';
import '../../css/l/lkae4mbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="lkae4mbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:icicles-48" /></template>
