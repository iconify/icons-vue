<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj347q2lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj347q2lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-long-line" /></template>
