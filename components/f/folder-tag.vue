<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlgfe8brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dlgfe8brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-tag" /></template>
