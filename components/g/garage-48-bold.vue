<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op_j2nylw.css';
import '../../css/b/bz0ghpbjx.css';
import '../../css/z/z9_87vb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="op_j2nylw"/><path class="bz0ghpbjx"/><path class="z9_87vb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garage-48-bold" /></template>
