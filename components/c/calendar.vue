<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe2u2sqvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe2u2sqvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:calendar" /></template>
