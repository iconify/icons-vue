<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiyuxlwou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiyuxlwou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-hexagon-filled" /></template>
