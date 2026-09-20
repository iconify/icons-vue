<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i25nmhjnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i25nmhjnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-indent-left-alignment-align-indent-paragraph-formatting-left-text" /></template>
