<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/burqsaclr.css';
import '../../css/z/zslpuabll.css';
import '../../css/m/mxw0qifka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="burqsaclr"/><path class="zslpuabll"/><path class="mxw0qifka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-down-20" /></template>
