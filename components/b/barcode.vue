<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hynd_kb9n.css';
import '../../css/n/ni0f_pbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hynd_kb9n"/><path class="ni0f_pbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:barcode" /></template>
