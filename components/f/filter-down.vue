<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kar8z_b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kar8z_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-down" /></template>
