<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep14q-bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep14q-bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-start-from-line" /></template>
