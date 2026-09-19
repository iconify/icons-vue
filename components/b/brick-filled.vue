<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5m-7ob2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5m-7ob2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brick-filled" /></template>
