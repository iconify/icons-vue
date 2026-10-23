<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc_mvgbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc_mvgbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-up" /></template>
