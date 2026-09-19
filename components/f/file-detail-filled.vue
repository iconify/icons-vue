<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-frsbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-frsbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-detail-filled" /></template>
