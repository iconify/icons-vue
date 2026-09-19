<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_tdev-jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":496};
const content = `<path class="s_tdev-jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:drop" /></template>
