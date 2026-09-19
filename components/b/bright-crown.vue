<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaapirbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaapirbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bright-crown" /></template>
