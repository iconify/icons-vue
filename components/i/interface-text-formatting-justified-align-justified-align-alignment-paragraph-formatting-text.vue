<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pze_dub6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pze_dub6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-justified-align-justified-align-alignment-paragraph-formatting-text" /></template>
