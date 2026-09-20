<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3assstja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z3assstja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graduation-cap-solid" /></template>
