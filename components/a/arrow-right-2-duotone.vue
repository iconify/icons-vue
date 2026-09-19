<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf5lj2b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf5lj2b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-2-duotone" /></template>
