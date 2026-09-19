<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke91w5bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ke91w5bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-3-square-fill" /></template>
