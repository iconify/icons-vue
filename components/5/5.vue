<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxef4ibam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":752};
const content = `<path class="lxef4ibam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:5" /></template>
