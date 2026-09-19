<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db0cu2b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db0cu2b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-filter-plus" /></template>
