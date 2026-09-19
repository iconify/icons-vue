<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbvsrd_3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbvsrd_3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-sit-overrides" /></template>
