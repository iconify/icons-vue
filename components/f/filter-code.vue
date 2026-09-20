<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksffx8bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksffx8bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-code" /></template>
