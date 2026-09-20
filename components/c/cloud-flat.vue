<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw_skj6xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cw_skj6xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cloud-flat" /></template>
