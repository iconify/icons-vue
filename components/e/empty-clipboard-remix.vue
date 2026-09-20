<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm0szfbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nm0szfbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:empty-clipboard-remix" /></template>
