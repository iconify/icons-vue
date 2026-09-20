<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ave6_-bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ave6_-bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:button-pause-circle-solid" /></template>
