<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu5dc43kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu5dc43kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:intex-pool-light" /></template>
