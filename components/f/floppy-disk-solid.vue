<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y971pxu-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y971pxu-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:floppy-disk-solid" /></template>
