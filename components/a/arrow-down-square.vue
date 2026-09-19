<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxe_zphpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mxe_zphpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-square" /></template>
