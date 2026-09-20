<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpng5rb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpng5rb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-box" /></template>
