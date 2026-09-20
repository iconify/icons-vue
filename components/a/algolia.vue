<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysxsjacgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysxsjacgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:algolia" /></template>
