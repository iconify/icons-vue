<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxqsgwbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yxqsgwbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-shrink-diagonal-1-solid" /></template>
