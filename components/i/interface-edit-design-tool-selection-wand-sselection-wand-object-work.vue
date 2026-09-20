<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp234nypf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tp234nypf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-design-tool-selection-wand-sselection-wand-object-work" /></template>
