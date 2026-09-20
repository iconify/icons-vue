<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk9no8l7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9no8l7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-down-fill" /></template>
