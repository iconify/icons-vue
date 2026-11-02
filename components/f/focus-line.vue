<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qus81wbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qus81wbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:focus-line" /></template>
