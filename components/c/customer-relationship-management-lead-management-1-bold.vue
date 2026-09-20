<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6rii6cio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6rii6cio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:customer-relationship-management-lead-management-1-bold" /></template>
