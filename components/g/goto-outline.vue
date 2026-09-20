<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqq645bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqq645bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:goto-outline" /></template>
