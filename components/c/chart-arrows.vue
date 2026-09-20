<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfpq3ebrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfpq3ebrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-arrows" /></template>
