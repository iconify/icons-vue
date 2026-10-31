<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozh7-gzxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozh7-gzxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-instance-bulk-round" /></template>
