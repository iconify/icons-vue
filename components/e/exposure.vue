<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/f/fqq8r6bth.css';
import '../../css/e/e3wcd1zdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="shu3xdl9q"/><circle class="fqq8r6bth"/><path class="e3wcd1zdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:exposure" /></template>
