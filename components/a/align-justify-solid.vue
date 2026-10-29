<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laf_138jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laf_138jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-justify-solid" /></template>
