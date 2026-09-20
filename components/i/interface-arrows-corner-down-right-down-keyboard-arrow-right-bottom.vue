<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8pxjbblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="x8pxjbblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-corner-down-right-down-keyboard-arrow-right-bottom" /></template>
