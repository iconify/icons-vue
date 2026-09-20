<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlkp8c8fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlkp8c8fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:filter-sort-lines-descending" /></template>
