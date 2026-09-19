<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ztjyrwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p4ztjyrwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-function-unverified" /></template>
