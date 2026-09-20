<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu6nytwut.css';
import '../../css/d/dt8zsopdi.css';
import '../../css/p/pg98fbbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu6nytwut"/><path class="dt8zsopdi"/><path class="pg98fbbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-docs-light" /></template>
