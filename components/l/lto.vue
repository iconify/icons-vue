<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_osqir4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_osqir4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lto" /></template>
