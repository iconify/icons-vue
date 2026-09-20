<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei6mfwbgr.css';
import '../../css/b/bc_0ayxta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ei6mfwbgr"/><path class="bc_0ayxta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cache-16" /></template>
