<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7wjvtb8g.css';
import '../../css/r/ra875cffg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wjvtb8g"/><path class="ra875cffg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-question-mark-fill" /></template>
