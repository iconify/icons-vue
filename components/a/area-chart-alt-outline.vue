<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqw06qb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cqw06qb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:area-chart-alt-outline" /></template>
