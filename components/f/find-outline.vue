<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smiup2bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="smiup2bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:find-outline" /></template>
