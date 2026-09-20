<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f386ljber.css';
import '../../css/x/xlllqtwpy.css';
import '../../css/b/b4wadacto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><path class="f386ljber"/><circle class="xlllqtwpy"/><path class="b4wadacto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:gps" /></template>
