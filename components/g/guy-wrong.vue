<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxjac9qul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxjac9qul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-wrong" /></template>
