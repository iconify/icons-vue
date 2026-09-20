<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1z0783yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1z0783yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-percentage" /></template>
