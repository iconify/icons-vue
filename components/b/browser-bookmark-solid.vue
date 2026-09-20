<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r594i1p_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r594i1p_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:browser-bookmark-solid" /></template>
