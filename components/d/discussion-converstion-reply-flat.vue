<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ows5bsbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ows5bsbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:discussion-converstion-reply-flat" /></template>
