<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lou9a14vc.css';
import '../../css/j/j2bufmatg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lou9a14vc"/><rect class="j2bufmatg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-stroke-12" /></template>
