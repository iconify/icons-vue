<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgk1dmbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgk1dmbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:christmas-tree" /></template>
