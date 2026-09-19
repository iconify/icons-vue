<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noad8bc2x.css';
import '../../css/v/vbgzj3b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="noad8bc2x"/><path class="vbgzj3b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:find-in-page" /></template>
