<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5h4td7le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5h4td7le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bentley" /></template>
