<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbgk3dx_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbgk3dx_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:calculator" /></template>
