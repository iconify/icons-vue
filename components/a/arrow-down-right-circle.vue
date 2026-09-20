<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p57so_sum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p57so_sum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-right-circle" /></template>
