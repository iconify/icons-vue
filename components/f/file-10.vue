<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j68dxzg3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j68dxzg3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-10" /></template>
