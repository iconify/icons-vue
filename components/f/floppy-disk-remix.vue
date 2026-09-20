<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xedcedcye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xedcedcye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:floppy-disk-remix" /></template>
