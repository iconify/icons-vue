<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjoxj5bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cjoxj5bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-check-remix" /></template>
