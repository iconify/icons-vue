<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew582eu4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew582eu4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:columns-4-solid" /></template>
