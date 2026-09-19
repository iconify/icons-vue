<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knl4x1tqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knl4x1tqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:life-ring" /></template>
