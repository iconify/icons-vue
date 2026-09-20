<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0q-oiapk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w0q-oiapk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:lightbulb-solid" /></template>
