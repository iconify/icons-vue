<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cluy_9boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cluy_9boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grip-vertical-solid" /></template>
