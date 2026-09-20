<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swr6hcp_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="swr6hcp_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:beaker-16" /></template>
