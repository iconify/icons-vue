<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-5qdfbve.css';
import '../../css/a/ammtthdlg.css';
import '../../css/b/bd01pac2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-5qdfbve"/><path class="ammtthdlg"/><path class="bd01pac2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-fryer-48" /></template>
