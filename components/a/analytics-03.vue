<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_vn6zxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd_vn6zxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:analytics-03" /></template>
