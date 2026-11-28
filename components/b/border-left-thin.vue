<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceh6ndd8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ceh6ndd8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-left-thin" /></template>
