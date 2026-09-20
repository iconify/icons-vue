<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrfsx9kxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rrfsx9kxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:key-remix" /></template>
