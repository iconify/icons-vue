<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1oh_mz-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1oh_mz-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-resize-diagonal" /></template>
