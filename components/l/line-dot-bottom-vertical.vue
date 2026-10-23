<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziw0cxgdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziw0cxgdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:line-dot-bottom-vertical" /></template>
