<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uks-53bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uks-53bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-arrow-down-outline" /></template>
