<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxt8ivbsc.css';
import '../../css/c/ckqvl2v2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxt8ivbsc"/><circle class="ckqvl2v2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:help-outline" /></template>
