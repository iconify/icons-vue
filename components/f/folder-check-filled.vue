<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcrybgb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcrybgb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-check-filled" /></template>
