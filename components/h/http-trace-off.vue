<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-nkfcrmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-nkfcrmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-trace-off" /></template>
