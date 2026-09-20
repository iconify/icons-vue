<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyqe-6bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyqe-6bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-pause" /></template>
