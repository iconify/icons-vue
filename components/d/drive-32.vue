<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfcf6nbxf.css';
import '../../css/x/x0bdrkbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfcf6nbxf"/><path clip-rule="evenodd" class="x0bdrkbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:drive-32" /></template>
