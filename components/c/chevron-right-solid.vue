<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rprjw-xhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rprjw-xhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-right-solid" /></template>
