<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky87bk4jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ky87bk4jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:family-48" /></template>
