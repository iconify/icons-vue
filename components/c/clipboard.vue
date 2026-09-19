<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w22f1_bsl.css';
import '../../css/c/cyx6qvb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w22f1_bsl"/><path class="cyx6qvb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:clipboard" /></template>
