<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qchr4-bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qchr4-bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:g-translate" /></template>
