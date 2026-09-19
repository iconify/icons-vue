<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7q9ekbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7q9ekbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:box-archive" /></template>
