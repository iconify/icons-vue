<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3pwlbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vm3pwlbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:grain" /></template>
