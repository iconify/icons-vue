<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr4hadbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4hadbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magnet-02" /></template>
