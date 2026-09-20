<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdv2mzb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdv2mzb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-down-box-fill" /></template>
