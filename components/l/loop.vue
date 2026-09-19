<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc8hhiglu.css';
import '../../css/e/e_vt-db2k.css';
import '../../css/z/zp9u2wb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="sc8hhiglu"/><path class="e_vt-db2k"/><path class="zp9u2wb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:loop" /></template>
