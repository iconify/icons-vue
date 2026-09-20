<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9y4lcbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f9y4lcbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hearing-deaf-1-solid" /></template>
