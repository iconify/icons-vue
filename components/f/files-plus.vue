<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzx7h-bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzx7h-bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:files-plus" /></template>
