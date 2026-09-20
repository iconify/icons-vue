<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1hs5njfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m1hs5njfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chair-remix" /></template>
