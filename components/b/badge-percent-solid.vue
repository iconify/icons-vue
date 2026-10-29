<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4_77zb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4_77zb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-percent-solid" /></template>
