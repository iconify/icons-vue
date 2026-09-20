<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wacgaabsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wacgaabsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-right-flip-right-object-work" /></template>
