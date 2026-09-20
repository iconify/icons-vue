<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_-ep6byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_-ep6byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-vertical-outline" /></template>
