<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx1nbrbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx1nbrbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:claude-fill" /></template>
