<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liqi8irpe.css';
import '../../css/h/hejk39zyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="liqi8irpe"/><circle class="hejk39zyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ionic" /></template>
