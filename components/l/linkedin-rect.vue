<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x848pdb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x848pdb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:linkedin-rect" /></template>
