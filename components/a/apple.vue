<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuxpu25hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uuxpu25hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:apple" /></template>
