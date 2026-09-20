<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-sbfr54f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-sbfr54f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-funnel" /></template>
