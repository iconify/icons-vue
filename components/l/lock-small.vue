<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofbry_bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ofbry_bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:lock-small" /></template>
