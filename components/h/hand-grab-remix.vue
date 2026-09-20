<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dawklnb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dawklnb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-grab-remix" /></template>
