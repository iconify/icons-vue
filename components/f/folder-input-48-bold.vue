<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw19-5bkm.css';
import '../../css/f/fv9h6ebsv.css';
import '../../css/r/r05k69bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lw19-5bkm"/><path class="fv9h6ebsv"/><path class="r05k69bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-input-48-bold" /></template>
