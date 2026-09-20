<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np7lh-0vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="np7lh-0vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-curve-right-down-remix" /></template>
