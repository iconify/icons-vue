<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlmn_lbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlmn_lbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:gopuram" /></template>
