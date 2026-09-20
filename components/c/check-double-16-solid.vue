<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0a7_rbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s0a7_rbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-double-16-solid" /></template>
