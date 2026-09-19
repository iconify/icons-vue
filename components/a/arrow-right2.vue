<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkdp20hab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xkdp20hab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-right2" /></template>
