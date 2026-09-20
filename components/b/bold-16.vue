<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdttaxgmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mdttaxgmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bold-16" /></template>
