<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xind5rutw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xind5rutw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-sort-ascending" /></template>
