<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn3zk-1ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yn3zk-1ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:arrow-up-outline" /></template>
