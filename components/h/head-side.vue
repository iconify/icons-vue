<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6gzs_b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6gzs_b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:head-side" /></template>
