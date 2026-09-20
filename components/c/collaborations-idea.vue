<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckxydgx1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ckxydgx1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:collaborations-idea" /></template>
