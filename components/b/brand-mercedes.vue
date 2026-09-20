<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7n7j88xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7n7j88xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-mercedes" /></template>
