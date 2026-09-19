<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds2j1pnfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds2j1pnfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:leaf" /></template>
