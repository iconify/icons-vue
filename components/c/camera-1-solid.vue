<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz19gyboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tz19gyboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-1-solid" /></template>
