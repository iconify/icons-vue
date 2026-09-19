<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jho5y_bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jho5y_bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:forward-solid" /></template>
