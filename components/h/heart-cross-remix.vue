<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-s12niqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-s12niqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:heart-cross-remix" /></template>
