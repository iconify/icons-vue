<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ift012_ct.css';
import '../../css/o/ockmixada.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ift012_ct"/><path class="ockmixada"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:basket" /></template>
