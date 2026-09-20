<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnuscxboo.css';
import '../../css/o/o44bltb0y.css';
import '../../css/x/xuokrglbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="fnuscxboo"/><path class="o44bltb0y"/><path clip-rule="evenodd" class="xuokrglbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:globus-bold-duotone" /></template>
