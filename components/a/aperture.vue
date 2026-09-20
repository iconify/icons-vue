<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqjfowblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqjfowblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:aperture" /></template>
