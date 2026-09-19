<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzedyzb9o.css';
import '../../css/o/o2d3vabmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzedyzb9o"/><path class="o2d3vabmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:description" /></template>
