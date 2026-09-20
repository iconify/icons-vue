<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5f7ddc1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g5f7ddc1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dark-dislay-mode-remix" /></template>
