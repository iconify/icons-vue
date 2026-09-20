<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0x8xlzqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s0x8xlzqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:lightning-box-solid" /></template>
