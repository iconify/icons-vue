<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp7x4_pfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="fp7x4_pfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-code-o" /></template>
