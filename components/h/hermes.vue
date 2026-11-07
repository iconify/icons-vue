<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx_bkof7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hx_bkof7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hermes" /></template>
