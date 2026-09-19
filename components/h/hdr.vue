<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phlszkbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phlszkbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hdr" /></template>
