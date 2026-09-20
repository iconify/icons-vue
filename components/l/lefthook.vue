<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocfthbcet.css';
import '../../css/u/uwe64fb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ocfthbcet"/><path class="uwe64fb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lefthook" /></template>
