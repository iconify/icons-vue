<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_0f8xzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_0f8xzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:linea" /></template>
