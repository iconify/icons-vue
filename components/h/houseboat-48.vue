<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmhs3ccli.css';
import '../../css/c/cy8_11dig.css';
import '../../css/o/o4-ileblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmhs3ccli"/><path class="cy8_11dig"/><path class="o4-ileblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:houseboat-48" /></template>
