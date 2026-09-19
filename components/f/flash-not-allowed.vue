<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no7dq_bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no7dq_bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:flash-not-allowed" /></template>
