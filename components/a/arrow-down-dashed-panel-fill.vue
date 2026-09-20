<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypoifcync.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypoifcync"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-dashed-panel-fill" /></template>
