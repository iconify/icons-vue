<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdfc7kbln.css';
import '../../css/p/plyl_b4bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gdfc7kbln"/><path class="plyl_b4bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:croissant-20" /></template>
