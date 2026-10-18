<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgigi6f3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgigi6f3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-distribute-end" /></template>
