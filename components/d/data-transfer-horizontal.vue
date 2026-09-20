<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzws7klud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzws7klud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:data-transfer-horizontal" /></template>
