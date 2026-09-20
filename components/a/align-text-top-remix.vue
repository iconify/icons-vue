<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my3y--76b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="my3y--76b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-text-top-remix" /></template>
