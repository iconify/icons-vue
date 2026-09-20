<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc06x8qpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc06x8qpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:filter-sort-lines-descending-bold" /></template>
