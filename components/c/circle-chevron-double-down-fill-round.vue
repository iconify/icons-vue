<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaw68pbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaw68pbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-down-fill-round" /></template>
