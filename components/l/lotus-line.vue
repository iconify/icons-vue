<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrn-ncbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrn-ncbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lotus-line" /></template>
