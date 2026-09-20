<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj9s757sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj9s757sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-donut-filled" /></template>
