<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvomrubdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvomrubdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drive-fill" /></template>
