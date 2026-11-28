<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsmt0crsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsmt0crsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-indian-rupee-solid" /></template>
