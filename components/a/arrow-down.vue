<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb5_nhbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="nb5_nhbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down" /></template>
