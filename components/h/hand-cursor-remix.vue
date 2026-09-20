<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oljv3-_nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oljv3-_nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-cursor-remix" /></template>
