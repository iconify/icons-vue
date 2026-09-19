<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1tvdnb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1tvdnb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:digg" /></template>
