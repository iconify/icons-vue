<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elk0dolzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="elk0dolzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:funnel" /></template>
