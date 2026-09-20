<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uilm590_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uilm590_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-program-filled" /></template>
