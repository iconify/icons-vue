<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2zn-v2ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o2zn-v2ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hard-disk-remix" /></template>
