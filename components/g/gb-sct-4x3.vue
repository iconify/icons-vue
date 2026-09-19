<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oln_hsbub.css';
import '../../css/b/bf6u4_bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="oln_hsbub"/><path transform="scale(128 160)" class="bf6u4_bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gb-sct-4x3" /></template>
