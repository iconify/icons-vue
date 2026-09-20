<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3wcr4bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3wcr4bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-outline" /></template>
