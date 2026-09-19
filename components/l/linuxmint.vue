<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrtqw4bir.css';
import '../../css/c/cat4-0bmn.css';
import '../../css/k/k-_vm5b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lrtqw4bir"/><path class="cat4-0bmn"/><path class="k-_vm5b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:linuxmint" /></template>
