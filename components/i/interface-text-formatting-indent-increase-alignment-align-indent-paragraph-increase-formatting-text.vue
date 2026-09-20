<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzoxg7_fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mzoxg7_fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-indent-increase-alignment-align-indent-paragraph-increase-formatting-text" /></template>
