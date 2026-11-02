<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osp5j8bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osp5j8bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-4-line" /></template>
