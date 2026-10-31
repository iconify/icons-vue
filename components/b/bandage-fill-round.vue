<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnnjw15f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqnnjw15f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandage-fill-round" /></template>
