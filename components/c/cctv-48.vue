<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-samsdi.css';
import '../../css/m/mmi04ob3v.css';
import '../../css/m/mbxjymbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tc-samsdi"/><path class="mmi04ob3v"/><path class="mbxjymbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cctv-48" /></template>
