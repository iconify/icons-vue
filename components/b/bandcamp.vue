<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lctjxf-_e.css';
import '../../css/f/fjc_j-bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lctjxf-_e"/><path class="fjc_j-bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bandcamp" /></template>
