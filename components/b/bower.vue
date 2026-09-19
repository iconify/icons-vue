<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfe2cdbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="cfe2cdbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:bower" /></template>
