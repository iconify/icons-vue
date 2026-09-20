<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq-680kix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hq-680kix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-move-solid" /></template>
