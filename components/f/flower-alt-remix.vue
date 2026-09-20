<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av10eewqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="av10eewqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flower-alt-remix" /></template>
