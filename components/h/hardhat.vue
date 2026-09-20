<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-ixacrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bi-ixacrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hardhat" /></template>
