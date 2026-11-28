<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osx1063bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osx1063bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:forward" /></template>
