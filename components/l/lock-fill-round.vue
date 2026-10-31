<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov_ptmbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov_ptmbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-fill-round" /></template>
