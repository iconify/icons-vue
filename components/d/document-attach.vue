<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kduvb0e1b.css';
import '../../css/q/qbzdmcc2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kduvb0e1b"/><path class="qbzdmcc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:document-attach" /></template>
