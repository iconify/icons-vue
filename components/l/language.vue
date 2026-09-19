<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue7-78_gf.css';
import '../../css/h/hndxaub8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue7-78_gf"/><path class="hndxaub8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:language" /></template>
