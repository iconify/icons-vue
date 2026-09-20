<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv05c1bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv05c1bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-dashboard-filled" /></template>
