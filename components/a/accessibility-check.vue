<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvtkjl28m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvtkjl28m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:accessibility-check" /></template>
