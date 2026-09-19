<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tu4mulbmj.css';
import '../../css/f/f5dyf_bxd.css';
import '../../css/t/t2siutbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tu4mulbmj"/><path class="f5dyf_bxd"/><path class="t2siutbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:bell-pepper" /></template>
