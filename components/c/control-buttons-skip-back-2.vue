<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf60akhnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sf60akhnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-skip-back-2" /></template>
