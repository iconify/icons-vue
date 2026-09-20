<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iho9wmb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iho9wmb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-cancel" /></template>
