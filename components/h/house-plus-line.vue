<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm_7zbc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_7zbc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-plus-line" /></template>
