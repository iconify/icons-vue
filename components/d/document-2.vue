<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzfilpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzfilpbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:document-2" /></template>
