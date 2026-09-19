<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrcqm7bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrcqm7bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:color-fill" /></template>
