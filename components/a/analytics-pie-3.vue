<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s85qfinjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s85qfinjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:analytics-pie-3" /></template>
