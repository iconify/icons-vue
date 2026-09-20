<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yei82dpsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yei82dpsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:diagram-tree" /></template>
