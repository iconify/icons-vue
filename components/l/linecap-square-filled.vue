<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6p40kx7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u6p40kx7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linecap-square-filled" /></template>
