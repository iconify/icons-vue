<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/f/fqq8r6bth.css';
import '../../css/k/kew9c1e5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="rotate(180 12 12)" class="shu3xdl9q"/><circle transform="rotate(180 12 12)" class="fqq8r6bth"/><path class="kew9c1e5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:add-circle" /></template>
