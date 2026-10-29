<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk9ov5cxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9ov5cxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bat-solid" /></template>
