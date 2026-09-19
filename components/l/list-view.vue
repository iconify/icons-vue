<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beg4g-64e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beg4g-64e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-view" /></template>
