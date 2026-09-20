<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdvnelb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdvnelb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:hardware-smart-watch" /></template>
