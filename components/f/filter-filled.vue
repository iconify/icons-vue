<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6xgii.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6xgii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:filter-filled" /></template>
