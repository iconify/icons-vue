<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-96robzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o-96robzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:archlinux" /></template>
