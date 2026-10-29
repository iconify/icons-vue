<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyo0a_ipl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyo0a_ipl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grid-2x2-solid" /></template>
