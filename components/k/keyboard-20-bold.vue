<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj49qk69z.css';
import '../../css/n/nq27wzbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vj49qk69z"/><path class="nq27wzbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:keyboard-20-bold" /></template>
