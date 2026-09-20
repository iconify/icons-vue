<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oevuh2bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oevuh2bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-question" /></template>
