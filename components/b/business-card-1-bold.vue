<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scks1v4hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scks1v4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-card-1-bold" /></template>
