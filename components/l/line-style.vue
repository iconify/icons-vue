<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c26rphbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c26rphbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:line-style" /></template>
