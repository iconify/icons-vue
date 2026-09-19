<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iejf6hdkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iejf6hdkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-left" /></template>
