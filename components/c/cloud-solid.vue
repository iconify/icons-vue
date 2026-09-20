<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tses_hxgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tses_hxgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-solid" /></template>
