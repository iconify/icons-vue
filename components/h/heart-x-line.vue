<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6vdgmb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6vdgmb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-x-line" /></template>
