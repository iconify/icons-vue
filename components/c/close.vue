<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzd3_cbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzd3_cbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:close" /></template>
