<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noij85b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noij85b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-line-down-outline" /></template>
