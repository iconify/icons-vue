<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz8djjb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wz8djjb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:copyright" /></template>
