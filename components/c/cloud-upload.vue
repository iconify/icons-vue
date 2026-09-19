<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq_rlaczy.css';
import '../../css/j/j-b8pcbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cq_rlaczy"/><path class="j-b8pcbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cloud-upload" /></template>
