<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzbu0ndxo.css';
import '../../css/z/zdzqfvyfv.css';
import '../../css/r/r5j29ko6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nzbu0ndxo"/><path class="zdzqfvyfv"/><path class="r5j29ko6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crib-20" /></template>
