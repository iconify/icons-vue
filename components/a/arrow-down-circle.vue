<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub6xj4edc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub6xj4edc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-circle" /></template>
