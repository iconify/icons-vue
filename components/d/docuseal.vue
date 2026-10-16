<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej0w98jpu.css';
import '../../css/m/mi3skhlne.css';
import '../../css/t/tcg1rxmwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<circle class="ej0w98jpu"/><path class="mi3skhlne"/><circle class="tcg1rxmwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:docuseal" /></template>
