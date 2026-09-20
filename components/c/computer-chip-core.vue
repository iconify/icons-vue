<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx3r8lbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx3r8lbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:computer-chip-core" /></template>
