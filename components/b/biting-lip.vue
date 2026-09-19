<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ln0hz112o.css';
import '../../css/x/xfnm38bzl.css';
import '../../css/t/tu6_0_bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ln0hz112o"/><path class="xfnm38bzl"/><path class="tu6_0_bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:biting-lip" /></template>
