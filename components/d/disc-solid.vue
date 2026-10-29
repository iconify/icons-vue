<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuuuxzbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuuuxzbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:disc-solid" /></template>
