<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgh789bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tgh789bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hifi-14" /></template>
