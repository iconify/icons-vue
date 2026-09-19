<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9g27pb1k.css';
import '../../css/s/soed_umth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9g27pb1k"/><path class="soed_umth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:boat-alt" /></template>
