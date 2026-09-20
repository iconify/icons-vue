<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmkq3nmdi.css';
import '../../css/g/g2yfz6ydr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmkq3nmdi"/><path class="g2yfz6ydr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:godot-assets" /></template>
