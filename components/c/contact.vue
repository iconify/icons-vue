<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vckfm4x5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vckfm4x5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:contact" /></template>
