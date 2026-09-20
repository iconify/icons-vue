<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0tav10am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0tav10am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-sharp-fill" /></template>
