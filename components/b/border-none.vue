<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_8dncb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i_8dncb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-none" /></template>
