<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8cxmrmln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8cxmrmln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:iud-24px" /></template>
