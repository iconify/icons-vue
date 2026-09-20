<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l130-fbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l130-fbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:building-2-remix" /></template>
