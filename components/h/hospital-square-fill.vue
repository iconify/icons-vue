<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ei-vbiq.css';
import '../../css/v/vexocobrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ei-vbiq"/><path class="vexocobrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hospital-square-fill" /></template>
