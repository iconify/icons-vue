<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn62dvbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sn62dvbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:check-correct-outline" /></template>
