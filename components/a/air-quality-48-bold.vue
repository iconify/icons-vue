<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7t94ub7i.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7t94ub7i"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-quality-48-bold" /></template>
