<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rke7srgws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rke7srgws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:deal-filled" /></template>
