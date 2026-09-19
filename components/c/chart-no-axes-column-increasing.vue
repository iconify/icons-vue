<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tysxy4bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tysxy4bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-no-axes-column-increasing" /></template>
