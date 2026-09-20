<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlitueb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlitueb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-horz-line" /></template>
