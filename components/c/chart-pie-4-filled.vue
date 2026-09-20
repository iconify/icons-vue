<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq0-71bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0-71bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-pie-4-filled" /></template>
