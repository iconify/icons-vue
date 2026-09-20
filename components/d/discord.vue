<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3kho1bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3kho1bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:discord" /></template>
