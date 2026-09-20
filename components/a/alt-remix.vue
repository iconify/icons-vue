<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1c8tbc2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x1c8tbc2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:alt-remix" /></template>
