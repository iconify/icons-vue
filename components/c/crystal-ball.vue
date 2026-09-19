<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lxhmx4bdy.css';
import '../../css/g/gy-xx9boc.css';
import '../../css/f/f11xa_ktj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lxhmx4bdy"/><path class="gy-xx9boc"/><path class="f11xa_ktj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:crystal-ball" /></template>
