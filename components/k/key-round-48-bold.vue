<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2oawlg-q.css';
import '../../css/z/z7_88imtg.css';
import '../../css/z/zbidebcoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2oawlg-q"/><path class="z7_88imtg"/><path class="zbidebcoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-round-48-bold" /></template>
