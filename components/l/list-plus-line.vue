<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8j_v3cco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8j_v3cco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-plus-line" /></template>
