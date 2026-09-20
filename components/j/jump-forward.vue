<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/j/jzzx7m_6o.css';
import '../../css/a/avwbqkbxp.css';
import '../../css/e/e8utxjb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="jzzx7m_6o"/><path class="avwbqkbxp"/><path class="e8utxjb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:jump-forward" /></template>
