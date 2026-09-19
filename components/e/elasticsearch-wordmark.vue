<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pew3ofbkh.css';
import '../../css/f/fp1_w-bip.css';
import '../../css/j/j57h7grwb.css';
import '../../css/o/opicw6a2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pew3ofbkh"/><path class="fp1_w-bip"/><path class="j57h7grwb"/><path class="opicw6a2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:elasticsearch-wordmark" /></template>
