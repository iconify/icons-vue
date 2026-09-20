<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zatu3h8ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zatu3h8ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-down" /></template>
