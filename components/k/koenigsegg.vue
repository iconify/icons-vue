<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po5guwbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po5guwbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:koenigsegg" /></template>
