<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz_xm9pdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz_xm9pdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-number-4" /></template>
