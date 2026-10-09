<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shh92ibos.css';
import '../../css/h/hw51tgbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shh92ibos"/><path class="hw51tgbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooling-tower-48" /></template>
