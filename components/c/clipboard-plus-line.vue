<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3oa-6rxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3oa-6rxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-plus-line" /></template>
