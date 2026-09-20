<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eislsacga.css';
import '../../css/h/hmcun9bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eislsacga"/><path class="hmcun9bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:dribbble-solid" /></template>
