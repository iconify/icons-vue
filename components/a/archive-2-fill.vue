<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uerla3dof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uerla3dof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-2-fill" /></template>
